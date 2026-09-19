<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2aou47wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="o2aou47wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:not-equal" {...props}></Icon>
