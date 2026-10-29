<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9zo-34oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9zo-34oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-minus" {...props}></Icon>
