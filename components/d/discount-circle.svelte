<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjuap2b5r.css';
import '../../css/e/eozwp4bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sjuap2b5r"/><path class="eozwp4bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:discount-circle" {...props}></Icon>
