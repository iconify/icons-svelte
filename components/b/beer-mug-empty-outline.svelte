<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nprwfihuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nprwfihuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:beer-mug-empty-outline" {...props}></Icon>
