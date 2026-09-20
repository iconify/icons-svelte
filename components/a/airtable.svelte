<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3mmgmnln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3mmgmnln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:airtable" {...props}></Icon>
