<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrnuwrb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrnuwrb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:forward-filled" {...props}></Icon>
