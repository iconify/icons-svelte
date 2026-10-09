<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjg5rdbcc.css';
import '../../css/b/bgc6dhdml.css';
import '../../css/n/nbcjn_bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pjg5rdbcc"/><path class="bgc6dhdml"/><path class="nbcjn_bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:belt-drive-20" {...props}></Icon>
