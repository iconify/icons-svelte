<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eod_tkbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="eod_tkbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grimace" {...props}></Icon>
