<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz7aj4fgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz7aj4fgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid-small" {...props}></Icon>
