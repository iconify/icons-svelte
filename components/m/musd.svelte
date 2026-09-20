<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj_u7vbcr.css';
import '../../css/x/xgapgabzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_u7vbcr"/><path class="xgapgabzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:musd" {...props}></Icon>
