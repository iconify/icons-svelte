<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhe2vibnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhe2vibnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:keyboard-bold" {...props}></Icon>
