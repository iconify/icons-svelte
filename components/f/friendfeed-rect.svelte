<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txlz-ovvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="txlz-ovvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:friendfeed-rect" {...props}></Icon>
