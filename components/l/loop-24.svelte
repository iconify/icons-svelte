<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k55cu9bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k55cu9bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:loop-24" {...props}></Icon>
