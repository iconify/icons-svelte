<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhlkjdbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhlkjdbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-6-filled" {...props}></Icon>
