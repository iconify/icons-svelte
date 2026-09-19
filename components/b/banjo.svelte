<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2wf-5mat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e2wf-5mat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:banjo" {...props}></Icon>
