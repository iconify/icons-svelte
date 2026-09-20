<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6y3pjc9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6y3pjc9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-pointer-click" {...props}></Icon>
