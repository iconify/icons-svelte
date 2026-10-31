<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow6zw0bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ow6zw0bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:italic-slash-solid" {...props}></Icon>
