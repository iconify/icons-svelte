<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h221lkbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h221lkbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cog-6-tooth-20-solid" {...props}></Icon>
