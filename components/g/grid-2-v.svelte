<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euhz4we2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euhz4we2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:grid-2-v" {...props}></Icon>
