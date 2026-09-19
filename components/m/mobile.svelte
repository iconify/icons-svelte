<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axdu2ub5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axdu2ub5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:mobile" {...props}></Icon>
