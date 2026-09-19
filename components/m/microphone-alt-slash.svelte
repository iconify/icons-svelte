<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb79k96ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="kb79k96ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:microphone-alt-slash" {...props}></Icon>
