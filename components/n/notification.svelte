<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smsq4b2xo.css';
import '../../css/a/amoelnz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="smsq4b2xo"/><path class="amoelnz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:notification" {...props}></Icon>
