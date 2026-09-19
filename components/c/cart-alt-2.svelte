<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv20ivdet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv20ivdet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-alt-2" {...props}></Icon>
