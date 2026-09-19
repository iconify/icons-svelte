<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jozfr4bht.css';
import '../../css/b/bgu4qnb1v.css';
import '../../css/d/dbndu9bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jozfr4bht"/><path class="bgu4qnb1v"/><path class="dbndu9bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:americanfootball" {...props}></Icon>
