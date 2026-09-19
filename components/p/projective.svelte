<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syj7luboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="syj7luboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:projective" {...props}></Icon>
