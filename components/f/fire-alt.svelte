<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfsnmwvsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfsnmwvsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fire-alt" {...props}></Icon>
