<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osqz-p07j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="osqz-p07j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:menu-left" {...props}></Icon>
