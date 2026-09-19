<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5jd9e2qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":512};
const content = `<path class="h5jd9e2qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:clothes-water" {...props}></Icon>
