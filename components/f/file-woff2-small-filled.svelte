<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks18lwb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ks18lwb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-woff2-small-filled" {...props}></Icon>
