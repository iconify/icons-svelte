<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cryayq36o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cryayq36o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-check" {...props}></Icon>
