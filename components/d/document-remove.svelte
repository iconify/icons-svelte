<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxwm93b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gxwm93b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:document-remove" {...props}></Icon>
