<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk9dg-bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk9dg-bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heart-plus" {...props}></Icon>
