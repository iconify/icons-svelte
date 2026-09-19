<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcin9tbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="vcin9tbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:battery" {...props}></Icon>
