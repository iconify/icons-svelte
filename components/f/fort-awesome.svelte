<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl-8ixi0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="gl-8ixi0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:fort-awesome" {...props}></Icon>
