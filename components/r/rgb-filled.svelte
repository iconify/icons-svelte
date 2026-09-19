<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taih8t-2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taih8t-2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rgb-filled" {...props}></Icon>
