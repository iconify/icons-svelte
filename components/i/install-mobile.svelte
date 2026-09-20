<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjn59jb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjn59jb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:install-mobile" {...props}></Icon>
