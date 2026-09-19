<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6q-fb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="th6q-fb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:couch" {...props}></Icon>
