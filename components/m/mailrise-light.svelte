<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re3lufbbf.css';
import '../../css/j/jh93d6jmw.css';
import '../../css/l/lq0ayphzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re3lufbbf"/><path class="jh93d6jmw"/><path class="lq0ayphzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailrise-light" {...props}></Icon>
