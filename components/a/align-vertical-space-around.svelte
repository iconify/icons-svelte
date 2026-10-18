<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4exklbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4exklbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-space-around" {...props}></Icon>
