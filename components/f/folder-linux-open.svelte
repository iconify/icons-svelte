<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yypzf8b8r.css';
import '../../css/d/dcz5ovbjt.css';
import '../../css/k/kyml_y7yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yypzf8b8r"/><path class="dcz5ovbjt"/><path class="kyml_y7yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-linux-open" {...props}></Icon>
