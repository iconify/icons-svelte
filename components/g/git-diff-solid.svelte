<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtk4rcckz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtk4rcckz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:git-diff-solid" {...props}></Icon>
