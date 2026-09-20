<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dko7ahb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dko7ahb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:git-commit-solid" {...props}></Icon>
