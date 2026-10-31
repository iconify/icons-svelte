<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzlj2ol0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzlj2ol0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:option-fill-round" {...props}></Icon>
