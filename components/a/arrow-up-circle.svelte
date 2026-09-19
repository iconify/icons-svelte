<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udf-wzd9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="udf-wzd9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-circle" {...props}></Icon>
