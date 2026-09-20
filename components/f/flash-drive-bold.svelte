<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyqf4h4lk.css';
import '../../css/w/wp__jovdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyqf4h4lk"/><path class="wp__jovdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flash-drive-bold" {...props}></Icon>
