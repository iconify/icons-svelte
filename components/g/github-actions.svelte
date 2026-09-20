<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxsdd63jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxsdd63jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:github-actions" {...props}></Icon>
