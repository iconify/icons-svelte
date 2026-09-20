<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5c9g5bsj.css';
import '../../css/z/zoxwfdcwf.css';
import '../../css/s/su0illb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5c9g5bsj"/><path class="zoxwfdcwf"/><path class="su0illb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:cloud-download" {...props}></Icon>
