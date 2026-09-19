<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhfzghafj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":582,"height":1000};
const content = `<path class="lhfzghafj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:lock-open" {...props}></Icon>
