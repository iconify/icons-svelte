<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw_y8qb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tw_y8qb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:moonwave" {...props}></Icon>
