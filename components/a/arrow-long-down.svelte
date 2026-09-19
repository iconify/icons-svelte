<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqh7qq44e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqh7qq44e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-long-down" {...props}></Icon>
