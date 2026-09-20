<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_papkbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_papkbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jira-light" {...props}></Icon>
