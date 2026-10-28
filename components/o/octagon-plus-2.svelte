<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyd8b1tgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyd8b1tgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-plus-2" {...props}></Icon>
