<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zubg1vb6f.css';
import '../../css/x/xivpjuiep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zubg1vb6f"/><path class="xivpjuiep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:hubot-24" {...props}></Icon>
