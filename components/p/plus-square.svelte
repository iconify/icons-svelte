<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae3o_2bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae3o_2bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plus-square" {...props}></Icon>
