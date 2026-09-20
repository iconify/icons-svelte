<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s958x7bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s958x7bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-settings-line" {...props}></Icon>
