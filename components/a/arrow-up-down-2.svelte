<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd_kjk6cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_kjk6cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-up-down-2" {...props}></Icon>
