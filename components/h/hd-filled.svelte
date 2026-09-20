<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvb6xnxqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvb6xnxqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hd-filled" {...props}></Icon>
