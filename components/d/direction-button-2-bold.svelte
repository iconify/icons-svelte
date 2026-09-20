<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2tgqkvzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2tgqkvzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:direction-button-2-bold" {...props}></Icon>
