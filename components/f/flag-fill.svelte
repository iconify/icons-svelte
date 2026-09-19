<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h10ri2bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h10ri2bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:flag-fill" {...props}></Icon>
