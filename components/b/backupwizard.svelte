<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5t8n1bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="x5t8n1bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:backupwizard" {...props}></Icon>
