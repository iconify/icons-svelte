<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/genx8sbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="genx8sbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pet-friendly" {...props}></Icon>
