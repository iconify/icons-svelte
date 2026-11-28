<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed85pwbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed85pwbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-dot-solid" {...props}></Icon>
