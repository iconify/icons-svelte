<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cquf3bccv.css';
import '../../css/q/qv0degibz.css';
import '../../css/j/jcweppbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cquf3bccv"/><path class="qv0degibz"/><path class="jcweppbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-rounded-bold" {...props}></Icon>
