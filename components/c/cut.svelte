<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqc1mzcmu.css';
import '../../css/q/q2cblpihb.css';
import '../../css/b/brfj9ob1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqc1mzcmu"/><path class="q2cblpihb"/><path class="brfj9ob1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cut" {...props}></Icon>
