<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfhs4vv5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lfhs4vv5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pause-circle-fill" {...props}></Icon>
