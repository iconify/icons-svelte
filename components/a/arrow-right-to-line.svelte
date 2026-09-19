<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc4bs3qme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jc4bs3qme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-right-to-line" {...props}></Icon>
