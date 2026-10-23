<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqdg6rbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqdg6rbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-circle-plus" {...props}></Icon>
