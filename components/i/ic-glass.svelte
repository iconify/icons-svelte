<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_svndbfa.css';
import '../../css/b/bexar7b7s.css';
import '../../css/m/mntxcwjfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224.88,"height":225};
const content = `<path class="f_svndbfa"/><path class="bexar7b7s"/><path class="mntxcwjfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ic-glass" {...props}></Icon>
