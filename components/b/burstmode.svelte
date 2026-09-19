<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuw81ib3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="kuw81ib3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:burstmode" {...props}></Icon>
