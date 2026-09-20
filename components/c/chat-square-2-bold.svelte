<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okcwy630f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="okcwy630f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-2-bold" {...props}></Icon>
