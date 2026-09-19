<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3j_yjh3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3j_yjh3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:livingroom-group" {...props}></Icon>
