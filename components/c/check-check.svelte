<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfk1jzxah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfk1jzxah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:check-check" {...props}></Icon>
