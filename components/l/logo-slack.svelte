<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9i_mvbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9i_mvbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-slack" {...props}></Icon>
