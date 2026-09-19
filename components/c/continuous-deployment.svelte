<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3e2ddq-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3e2ddq-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:continuous-deployment" {...props}></Icon>
