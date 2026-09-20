<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq303r2fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq303r2fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-edit-alt-1-line" {...props}></Icon>
