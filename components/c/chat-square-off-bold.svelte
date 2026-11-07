<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erra6gogy.css';
import '../../css/i/ix_x8gb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erra6gogy"/><path class="ix_x8gb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-off-bold" {...props}></Icon>
