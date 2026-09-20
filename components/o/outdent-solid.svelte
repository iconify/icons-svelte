<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2iw6y11v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w2iw6y11v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:outdent-solid" {...props}></Icon>
