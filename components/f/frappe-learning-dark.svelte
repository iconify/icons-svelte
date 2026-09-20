<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb0w0iykn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nb0w0iykn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-learning-dark" {...props}></Icon>
