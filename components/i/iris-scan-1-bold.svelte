<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd8vn1rbq.css';
import '../../css/y/yuj1lj0ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd8vn1rbq"/><path class="yuj1lj0ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:iris-scan-1-bold" {...props}></Icon>
