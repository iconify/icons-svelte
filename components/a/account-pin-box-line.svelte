<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u85shjb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u85shjb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-pin-box-line" {...props}></Icon>
