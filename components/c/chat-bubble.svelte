<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8qo20b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8qo20b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-bubble" {...props}></Icon>
