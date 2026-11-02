<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqd_eqbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqd_eqbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-cny-fill" {...props}></Icon>
