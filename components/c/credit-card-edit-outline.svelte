<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3yi4ibis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3yi4ibis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-edit-outline" {...props}></Icon>
