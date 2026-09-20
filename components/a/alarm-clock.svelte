<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlnc8j4gt.css';
import '../../css/w/w-f7zlbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hlnc8j4gt"/><path class="w-f7zlbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:alarm-clock" {...props}></Icon>
