<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-xzn5b1r.css';
import '../../css/a/avruddccb.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 t-xzn5b1r"/><path class="avruddccb clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:book-solid" {...props}></Icon>
