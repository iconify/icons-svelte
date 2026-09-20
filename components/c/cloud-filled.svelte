<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_-885d7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_-885d7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-filled" {...props}></Icon>
