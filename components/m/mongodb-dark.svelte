<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msfe4rzvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":257};
const content = `<path class="msfe4rzvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mongodb-dark" {...props}></Icon>
