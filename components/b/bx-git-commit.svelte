<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xageqtutm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xageqtutm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-git-commit" {...props}></Icon>
