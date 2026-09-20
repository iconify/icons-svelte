<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fszjscclm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fszjscclm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-down-circle" {...props}></Icon>
