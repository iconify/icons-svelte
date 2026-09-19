<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpyvibbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpyvibbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:globe-asia-australia" {...props}></Icon>
