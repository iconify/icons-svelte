<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_4n6ub8r.css';
import '../../css/t/tn4_b_t8u.css';
import '../../css/o/op37kihor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i_4n6ub8r"/><path class="tn4_b_t8u"/><path class="op37kihor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:jule" {...props}></Icon>
