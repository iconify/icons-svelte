<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm1hi_b-d.css';
import '../../css/f/ffq0z92oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm1hi_b-d"/><path class="ffq0z92oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:picture-in-picture" {...props}></Icon>
