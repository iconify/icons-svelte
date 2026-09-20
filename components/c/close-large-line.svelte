<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq9jq0-sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq9jq0-sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:close-large-line" {...props}></Icon>
