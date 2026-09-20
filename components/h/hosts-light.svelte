<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1sz4db_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v1sz4db_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hosts-light" {...props}></Icon>
