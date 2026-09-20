<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7cy4nbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7cy4nbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:caret-right-small" {...props}></Icon>
