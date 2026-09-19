<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlf1zvq-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlf1zvq-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-circle-remove" {...props}></Icon>
