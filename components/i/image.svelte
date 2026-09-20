<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo696l5nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bo696l5nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:image" {...props}></Icon>
