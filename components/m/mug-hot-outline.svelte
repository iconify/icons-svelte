<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwb4vcbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwb4vcbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:mug-hot-outline" {...props}></Icon>
