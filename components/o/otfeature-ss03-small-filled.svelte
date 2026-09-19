<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnuadmb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gnuadmb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-ss03-small-filled" {...props}></Icon>
