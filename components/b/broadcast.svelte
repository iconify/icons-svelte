<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo9kftbtp.css';
import '../../css/u/u2hnframu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo9kftbtp"/><path class="u2hnframu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:broadcast" {...props}></Icon>
