<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka8y21bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka8y21bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:inbox-remove-outline" {...props}></Icon>
