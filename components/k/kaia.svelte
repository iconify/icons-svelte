<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrmg7_fcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrmg7_fcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kaia" {...props}></Icon>
