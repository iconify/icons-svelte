<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsjs4_b4y.css';
import '../../css/c/ckbg2-b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsjs4_b4y"/><path class="ckbg2-b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-symlink-24" {...props}></Icon>
