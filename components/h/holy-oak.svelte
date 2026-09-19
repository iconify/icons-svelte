<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvl_8rp-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvl_8rp-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:holy-oak" {...props}></Icon>
