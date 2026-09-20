<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_44q3bqb.css';
import '../../css/c/chv7bcx-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_44q3bqb"/><path class="chv7bcx-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock-five" {...props}></Icon>
