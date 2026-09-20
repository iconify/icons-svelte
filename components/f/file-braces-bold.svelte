<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cguuphizu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cguuphizu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-braces-bold" {...props}></Icon>
