<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_3p-cbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l_3p-cbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flexible-star" {...props}></Icon>
