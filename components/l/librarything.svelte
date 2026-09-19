<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q19f3yg1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q19f3yg1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:librarything" {...props}></Icon>
