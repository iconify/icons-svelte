<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1bx12_kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":200};
const content = `<path class="v1bx12_kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:crystal" {...props}></Icon>
