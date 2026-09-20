<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv1mz-i2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv1mz-i2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:notification-filled" {...props}></Icon>
