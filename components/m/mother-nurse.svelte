<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/davgogbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="davgogbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mother-nurse" {...props}></Icon>
