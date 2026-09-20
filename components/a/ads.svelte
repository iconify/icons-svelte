<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieuuixy1o.css';
import '../../css/m/m1si3hbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieuuixy1o"/><path class="m1si3hbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ads" {...props}></Icon>
