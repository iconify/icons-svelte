<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo-kw6rdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="mo-kw6rdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:microphone" {...props}></Icon>
