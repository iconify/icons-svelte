<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u43nocbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u43nocbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bar-left" {...props}></Icon>
