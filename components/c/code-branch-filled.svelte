<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kio_w0bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kio_w0bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-branch-filled" {...props}></Icon>
