<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua2we0bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ua2we0bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pinterest" {...props}></Icon>
