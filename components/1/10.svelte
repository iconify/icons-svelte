<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfqv7u9dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfqv7u9dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:10" {...props}></Icon>
