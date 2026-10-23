<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgng7ybrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgng7ybrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-pen" {...props}></Icon>
