<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tanll1bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tanll1bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:razor" {...props}></Icon>
