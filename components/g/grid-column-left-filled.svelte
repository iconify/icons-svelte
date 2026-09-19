<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j64dr1bxs.css';
import '../../css/b/bhbvqjyxk.css';
import '../../css/g/gtn46m-jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="j64dr1bxs"/><rect class="bhbvqjyxk"/><rect class="gtn46m-jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-column-left-filled" {...props}></Icon>
