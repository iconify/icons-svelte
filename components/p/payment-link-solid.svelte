<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msm96vi3m.css';
import '../../css/h/hstvx30-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msm96vi3m"/><path class="hstvx30-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:payment-link-solid" {...props}></Icon>
