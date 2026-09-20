<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh5wkgpim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5wkgpim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-add-line" {...props}></Icon>
