<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhq5bu_3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bhq5bu_3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:check" {...props}></Icon>
