<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ompvwdblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ompvwdblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-scissors" {...props}></Icon>
