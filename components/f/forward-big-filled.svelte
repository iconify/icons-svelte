<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkjo60blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkjo60blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:forward-big-filled" {...props}></Icon>
