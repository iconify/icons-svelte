<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wegkc6b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wegkc6b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:grain" {...props}></Icon>
