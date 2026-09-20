<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjl4lfbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjl4lfbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-settings-variant" {...props}></Icon>
