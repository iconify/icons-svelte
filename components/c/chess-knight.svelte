<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/begoqnbqd.css';
import '../../css/x/xwizttm5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="begoqnbqd"/><path class="xwizttm5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chess-knight" {...props}></Icon>
