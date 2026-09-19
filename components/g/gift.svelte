<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnykaab2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnykaab2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:gift" {...props}></Icon>
