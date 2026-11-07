<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9benlbfz.css';
import '../../css/k/kemsso1tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9benlbfz"/><path clip-rule="evenodd" class="kemsso1tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:devices-bold" {...props}></Icon>
