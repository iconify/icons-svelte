<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a104jn7sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a104jn7sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:fax" {...props}></Icon>
