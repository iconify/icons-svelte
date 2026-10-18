<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4aws_orj.css';
import '../../css/l/l-h9c6bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q4aws_orj"/><path class="l-h9c6bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expansion-vessel-20" {...props}></Icon>
