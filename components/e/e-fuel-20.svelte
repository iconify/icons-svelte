<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwh1q-fzk.css';
import '../../css/o/okro7rlip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwh1q-fzk"/><path class="okro7rlip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-fuel-20" {...props}></Icon>
