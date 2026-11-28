<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj5go6byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5go6byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:circle-9" {...props}></Icon>
