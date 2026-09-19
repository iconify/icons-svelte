<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw83j6bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw83j6bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:credit-card" {...props}></Icon>
