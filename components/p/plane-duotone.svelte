<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrnm6zb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xrnm6zb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-duotone" {...props}></Icon>
