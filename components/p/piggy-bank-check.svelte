<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyzxacc4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyzxacc4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:piggy-bank-check" {...props}></Icon>
