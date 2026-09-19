<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw36-dbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw36-dbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:hamburger-md" {...props}></Icon>
