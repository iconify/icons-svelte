<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6c9-14m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aa6c9-14m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:redhat" {...props}></Icon>
