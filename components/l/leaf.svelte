<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udi-aab5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udi-aab5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:leaf" {...props}></Icon>
