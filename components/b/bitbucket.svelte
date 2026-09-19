<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8wydab-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j8wydab-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:bitbucket" {...props}></Icon>
