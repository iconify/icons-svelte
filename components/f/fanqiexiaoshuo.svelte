<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql_ckoerv.css';
import '../../css/p/p6q8xum6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ql_ckoerv"/><path class="p6q8xum6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fanqiexiaoshuo" {...props}></Icon>
