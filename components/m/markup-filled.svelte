<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbwx9qiay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbwx9qiay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:markup-filled" {...props}></Icon>
