<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmbw-t3wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nmbw-t3wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:download-small" {...props}></Icon>
