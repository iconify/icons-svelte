<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnvfmbbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnvfmbbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:figma-broken" {...props}></Icon>
