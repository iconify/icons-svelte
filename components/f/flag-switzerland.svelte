<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1t_bgblg.css';
import '../../css/l/ljyjriblh.css';
import '../../css/q/qaf2rb42e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="i1t_bgblg"/><path class="ljyjriblh"/><path class="qaf2rb42e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-switzerland" {...props}></Icon>
