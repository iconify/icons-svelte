<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckfta7erj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckfta7erj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nvm" {...props}></Icon>
