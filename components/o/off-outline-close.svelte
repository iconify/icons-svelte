<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edwif1blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edwif1blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:off-outline-close" {...props}></Icon>
