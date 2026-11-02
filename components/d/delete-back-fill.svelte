<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvmb6gb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvmb6gb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-back-fill" {...props}></Icon>
