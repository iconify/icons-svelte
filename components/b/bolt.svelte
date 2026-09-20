<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbj_egiqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bbj_egiqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bolt" {...props}></Icon>
