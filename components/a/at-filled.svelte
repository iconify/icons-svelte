<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hifub2buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hifub2buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:at-filled" {...props}></Icon>
