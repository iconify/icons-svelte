<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuq627b0r.css';
import '../../css/c/c5qcubb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuq627b0r"/><path class="c5qcubb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-right-circle" {...props}></Icon>
