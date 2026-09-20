<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az2jqwfwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az2jqwfwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:graphite" {...props}></Icon>
