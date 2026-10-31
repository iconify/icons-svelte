<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnv1knkjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnv1knkjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-u" {...props}></Icon>
