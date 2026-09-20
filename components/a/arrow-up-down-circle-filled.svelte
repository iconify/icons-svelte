<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhehljbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhehljbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-up-down-circle-filled" {...props}></Icon>
