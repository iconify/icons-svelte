<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3g732bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3g732bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-pen-line" {...props}></Icon>
