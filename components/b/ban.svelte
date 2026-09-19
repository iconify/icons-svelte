<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7u48b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lv7u48b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ban" {...props}></Icon>
