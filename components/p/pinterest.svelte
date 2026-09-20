<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onr-ktbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onr-ktbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:pinterest" {...props}></Icon>
