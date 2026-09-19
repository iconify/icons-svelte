<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2wusww1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2wusww1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-check" {...props}></Icon>
