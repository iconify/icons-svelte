<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwp5anzju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwp5anzju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-left" {...props}></Icon>
