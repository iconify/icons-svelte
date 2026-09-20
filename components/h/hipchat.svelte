<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd68dem-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd68dem-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:hipchat" {...props}></Icon>
