<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikjw0blbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ikjw0blbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:jira" {...props}></Icon>
