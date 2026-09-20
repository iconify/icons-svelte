<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvbn4vepc.css';
import '../../css/k/kq37wbc8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvbn4vepc"/><path class="kq37wbc8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:paypal" {...props}></Icon>
