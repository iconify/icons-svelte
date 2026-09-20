<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vouq7mimd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vouq7mimd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:box" {...props}></Icon>
