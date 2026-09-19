<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h33_-nbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="h33_-nbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:researchgate" {...props}></Icon>
