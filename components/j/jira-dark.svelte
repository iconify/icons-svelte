<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8en0-mhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8en0-mhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jira-dark" {...props}></Icon>
