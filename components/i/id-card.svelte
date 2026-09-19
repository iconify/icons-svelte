<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi2mgubtd.css';
import '../../css/f/fgk1ekbcn.css';
import '../../css/j/j0k3qqbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi2mgubtd"/><path class="fgk1ekbcn"/><path class="j0k3qqbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:id-card" {...props}></Icon>
