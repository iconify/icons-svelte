<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exn257bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exn257bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:play-solid" {...props}></Icon>
