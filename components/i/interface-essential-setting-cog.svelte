<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc5li9bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oc5li9bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-setting-cog" {...props}></Icon>
