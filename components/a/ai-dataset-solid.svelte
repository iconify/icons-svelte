<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vajhqobue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vajhqobue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-dataset-solid" {...props}></Icon>
