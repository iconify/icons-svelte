<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvnb4t_-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kvnb4t_-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:database-arrow-right" {...props}></Icon>
