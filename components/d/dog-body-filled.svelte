<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzv03fbgv.css';
import '../../css/k/kid6f5maa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzv03fbgv"/><path class="kid6f5maa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dog-body-filled" {...props}></Icon>
