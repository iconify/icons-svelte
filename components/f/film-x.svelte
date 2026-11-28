<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztlf6xbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztlf6xbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film-x" {...props}></Icon>
