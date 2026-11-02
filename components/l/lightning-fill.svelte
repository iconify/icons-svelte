<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng1wm4grq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1wm4grq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lightning-fill" {...props}></Icon>
