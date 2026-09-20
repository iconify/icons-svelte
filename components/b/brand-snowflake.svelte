<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g69hyt1hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g69hyt1hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-snowflake" {...props}></Icon>
