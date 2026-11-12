<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mshnxfvng.css';
import '../../css/j/jh93d6jmw.css';
import '../../css/n/ntjhm5bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mshnxfvng"/><path class="jh93d6jmw"/><path class="ntjhm5bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailrise-light" {...props}></Icon>
