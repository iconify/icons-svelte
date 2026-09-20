<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6v5r2biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6v5r2biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:menu-application" {...props}></Icon>
