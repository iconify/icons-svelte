<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze7hdcc3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze7hdcc3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-documents-solid" {...props}></Icon>
