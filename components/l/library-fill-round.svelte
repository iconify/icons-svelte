<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwwb8k8on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwwb8k8on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:library-fill-round" {...props}></Icon>
