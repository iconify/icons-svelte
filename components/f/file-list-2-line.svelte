<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr3ricc3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr3ricc3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-list-2-line" {...props}></Icon>
