<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw_nd3bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw_nd3bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:keyboard-1" {...props}></Icon>
