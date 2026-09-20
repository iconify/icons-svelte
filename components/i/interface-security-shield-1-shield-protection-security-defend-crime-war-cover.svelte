<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ej5wb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e5ej5wb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-security-shield-1-shield-protection-security-defend-crime-war-cover" {...props}></Icon>
