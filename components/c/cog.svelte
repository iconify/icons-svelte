<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvi257b1u.css';
import '../../css/k/kyxjq5b8z.css';
import '../../css/p/p_1scj-cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vvi257b1u"/><path class="kyxjq5b8z"/><path class="p_1scj-cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:cog" {...props}></Icon>
