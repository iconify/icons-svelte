<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-ibu-b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-ibu-b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:download" {...props}></Icon>
