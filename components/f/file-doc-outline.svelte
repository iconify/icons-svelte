<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3ex7_fmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3ex7_fmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-doc-outline" {...props}></Icon>
