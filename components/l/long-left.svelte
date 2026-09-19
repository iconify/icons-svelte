<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifkq_huon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifkq_huon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:long-left" {...props}></Icon>
