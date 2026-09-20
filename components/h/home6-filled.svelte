<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mre_tg15u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mre_tg15u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home6-filled" {...props}></Icon>
