<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dez_3qb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dez_3qb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rhombus-solid" {...props}></Icon>
