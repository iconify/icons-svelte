<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-w7pwb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="o-w7pwb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bamboo" {...props}></Icon>
