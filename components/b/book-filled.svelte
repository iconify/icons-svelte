<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxb2qnb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxb2qnb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:book-filled" {...props}></Icon>
