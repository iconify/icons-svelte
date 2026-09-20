<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-c7f4bry.css';
import '../../css/t/tvqx1abby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s-c7f4bry"/><path class="tvqx1abby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-stack" {...props}></Icon>
