<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chdr2jb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chdr2jb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-check-solid" {...props}></Icon>
