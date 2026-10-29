<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fna3zcc3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fna3zcc3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-minus-solid" {...props}></Icon>
