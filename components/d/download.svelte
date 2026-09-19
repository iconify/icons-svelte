<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osp4wzbqk.css';
import '../../css/u/uotgxeb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osp4wzbqk"/><path class="uotgxeb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:download" {...props}></Icon>
