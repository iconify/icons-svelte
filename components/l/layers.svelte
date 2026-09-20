<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ls-cb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m4ls-cb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:layers" {...props}></Icon>
