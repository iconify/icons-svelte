<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho1tdhbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho1tdhbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:coral" {...props}></Icon>
