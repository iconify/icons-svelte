<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqt9uxmcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt9uxmcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:clerk" {...props}></Icon>
