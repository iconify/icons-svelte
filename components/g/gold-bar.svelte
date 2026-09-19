<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc1h4-8rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uc1h4-8rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gold-bar" {...props}></Icon>
