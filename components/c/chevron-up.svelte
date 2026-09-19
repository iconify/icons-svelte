<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjk91bc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjk91bc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:chevron-up" {...props}></Icon>
