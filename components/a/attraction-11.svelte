<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_gup7b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="o_gup7b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:attraction-11" {...props}></Icon>
