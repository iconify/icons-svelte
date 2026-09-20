<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv82tk.css';
import '../../css/y/yi8b0f.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-30.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv82tk"/><path class="yi8b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:heart-twotone" {...props}></Icon>
