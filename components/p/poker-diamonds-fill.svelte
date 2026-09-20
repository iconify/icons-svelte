<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qenkhxbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qenkhxbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:poker-diamonds-fill" {...props}></Icon>
