<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8ry8ubus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v8ry8ubus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-left-circle-fill" {...props}></Icon>
