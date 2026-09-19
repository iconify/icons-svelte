<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a69wlg18g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a69wlg18g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:jinja" {...props}></Icon>
