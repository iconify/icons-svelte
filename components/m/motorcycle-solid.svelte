<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyp5a7r6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyp5a7r6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:motorcycle-solid" {...props}></Icon>
