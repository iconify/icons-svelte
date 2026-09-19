<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l99px9b1j.css';
import '../../css/z/zhugi-b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l99px9b1j"/><path class="zhugi-b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:ip" {...props}></Icon>
