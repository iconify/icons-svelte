<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw78bx2nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qw78bx2nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:money-bill" {...props}></Icon>
