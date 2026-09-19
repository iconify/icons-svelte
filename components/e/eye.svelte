<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlee1f3sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1280};
const content = `<path class="mlee1f3sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:eye" {...props}></Icon>
