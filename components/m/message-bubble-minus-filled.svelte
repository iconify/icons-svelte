<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g97jyebka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g97jyebka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-minus-filled" {...props}></Icon>
