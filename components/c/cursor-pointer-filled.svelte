<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iamwjnotf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iamwjnotf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-pointer-filled" {...props}></Icon>
