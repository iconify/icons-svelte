<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr6lkb-0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr6lkb-0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:circle-chevron-left" {...props}></Icon>
