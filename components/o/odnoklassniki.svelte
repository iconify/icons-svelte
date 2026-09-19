<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyi-f8nlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":579.274,"height":1000};
const content = `<path class="xyi-f8nlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:odnoklassniki" {...props}></Icon>
