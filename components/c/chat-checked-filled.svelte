<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egn8adbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egn8adbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-checked-filled" {...props}></Icon>
