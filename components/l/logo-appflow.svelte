<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuqgrccsg.css';
import '../../css/o/obu153b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yuqgrccsg"/><path class="obu153b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-appflow" {...props}></Icon>
