<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5_tenb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k5_tenb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward-60" {...props}></Icon>
