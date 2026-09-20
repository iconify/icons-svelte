<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unxzl60gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unxzl60gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openjdk" {...props}></Icon>
