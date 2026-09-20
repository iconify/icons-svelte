<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s31lv9kcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s31lv9kcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align-letter-right" {...props}></Icon>
