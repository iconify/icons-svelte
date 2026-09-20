<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydwz119uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydwz119uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:message-fill" {...props}></Icon>
