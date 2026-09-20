<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lph5zbctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lph5zbctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-fill" {...props}></Icon>
