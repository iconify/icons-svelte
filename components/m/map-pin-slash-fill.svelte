<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2-sshxfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n2-sshxfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:map-pin-slash-fill" {...props}></Icon>
