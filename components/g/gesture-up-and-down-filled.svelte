<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op0gkacgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op0gkacgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-up-and-down-filled" {...props}></Icon>
