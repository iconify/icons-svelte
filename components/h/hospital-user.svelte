<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf5j8vb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qf5j8vb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hospital-user" {...props}></Icon>
