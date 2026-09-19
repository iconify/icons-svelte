<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4ofafy9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="p4ofafy9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:left-circle" {...props}></Icon>
