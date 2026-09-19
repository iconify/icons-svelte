<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v74ll-bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v74ll-bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbed-star" {...props}></Icon>
