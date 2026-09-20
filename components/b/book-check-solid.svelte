<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf4xfdbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf4xfdbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-check-solid" {...props}></Icon>
