<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhwmv1zcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="jhwmv1zcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:box" {...props}></Icon>
