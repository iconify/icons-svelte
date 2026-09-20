<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrhb9mvxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrhb9mvxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:credit-card" {...props}></Icon>
