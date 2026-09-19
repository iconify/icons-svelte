<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4v-hpbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="l4v-hpbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:quotes" {...props}></Icon>
