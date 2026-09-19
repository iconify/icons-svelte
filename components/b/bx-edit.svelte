<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klqzlfb6u.css';
import '../../css/b/bfbxrvtsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klqzlfb6u"/><path class="bfbxrvtsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-edit" {...props}></Icon>
