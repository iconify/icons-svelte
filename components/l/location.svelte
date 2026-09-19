<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oysno6b8h.css';
import '../../css/i/ijdqjaczl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="oysno6b8h"/><path class="ijdqjaczl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:location" {...props}></Icon>
