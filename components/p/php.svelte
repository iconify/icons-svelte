<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkji4xtjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkji4xtjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:php" {...props}></Icon>
