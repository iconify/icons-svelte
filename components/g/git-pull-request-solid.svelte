<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue7jy582w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue7jy582w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-pull-request-solid" {...props}></Icon>
