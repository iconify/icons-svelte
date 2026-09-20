<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evkgmvbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evkgmvbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:play-circle3-filled" {...props}></Icon>
