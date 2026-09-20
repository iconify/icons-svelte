<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu0_6bbna.css';
import '../../css/o/obz-b-bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pu0_6bbna"/><path class="obz-b-bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-mobile" {...props}></Icon>
