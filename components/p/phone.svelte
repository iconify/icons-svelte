<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smgpfq.css';
import '../../css/s/so-from-62.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smgpfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone" {...props}></Icon>
