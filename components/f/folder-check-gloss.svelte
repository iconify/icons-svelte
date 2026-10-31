<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8clm2bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8clm2bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-check-gloss" {...props}></Icon>
