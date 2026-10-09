<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwpjg0bhd.css';
import '../../css/c/c_dqrlbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lwpjg0bhd"/><path class="c_dqrlbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:golf-20-bold" {...props}></Icon>
