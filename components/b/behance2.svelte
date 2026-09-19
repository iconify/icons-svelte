<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0v9jjbyk.css';
import '../../css/x/x3ykjurxz.css';
import '../../css/c/czxvcbrup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r0v9jjbyk"/><path class="x3ykjurxz"/><path class="czxvcbrup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:behance2" {...props}></Icon>
