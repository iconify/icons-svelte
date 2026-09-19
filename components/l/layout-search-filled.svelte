<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhbvqjyxk.css';
import '../../css/g/gyghflb6y.css';
import '../../css/j/j64dr1bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="bhbvqjyxk"/><path class="gyghflb6y"/><rect class="j64dr1bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layout-search-filled" {...props}></Icon>
