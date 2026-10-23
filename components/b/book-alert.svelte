<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc2jqdb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc2jqdb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-alert" {...props}></Icon>
