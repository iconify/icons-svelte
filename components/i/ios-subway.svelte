<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at9237b-b.css';
import '../../css/t/t0f-scclc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="at9237b-b"/><path class="t0f-scclc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-subway" {...props}></Icon>
