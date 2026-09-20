<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfi026obj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hfi026obj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ethereum" {...props}></Icon>
