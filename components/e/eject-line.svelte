<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfcivp-ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfcivp-ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:eject-line" {...props}></Icon>
