<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh2y6xbeo.css';
import '../../css/y/yx6kzzz_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh2y6xbeo"/><path class="yx6kzzz_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:push-notification-2" {...props}></Icon>
