<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m275f1bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m275f1bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-x" {...props}></Icon>
