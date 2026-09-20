<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvx4y13re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvx4y13re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-jcb" {...props}></Icon>
