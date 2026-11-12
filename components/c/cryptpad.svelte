<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwakcgbjk.css';
import '../../css/j/jhj59op0p.css';
import '../../css/q/qu56y6rrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwakcgbjk"/><path class="jhj59op0p"/><path class="qu56y6rrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cryptpad" {...props}></Icon>
