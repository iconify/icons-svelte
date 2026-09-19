<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obc9sh-4y.css';
import '../../css/j/jm-104bqg.css';
import '../../css/f/frztjqr5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obc9sh-4y"/><path class="jm-104bqg"/><path class="frztjqr5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-school" {...props}></Icon>
