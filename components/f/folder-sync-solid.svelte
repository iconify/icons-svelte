<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqs8dcnai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqs8dcnai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-sync-solid" {...props}></Icon>
