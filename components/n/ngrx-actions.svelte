<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilvr2qb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="ilvr2qb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ngrx-actions" {...props}></Icon>
