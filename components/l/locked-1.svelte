<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tetbrrbka.css';
import '../../css/j/j9auzlb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tetbrrbka"/><path class="j9auzlb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:locked-1" {...props}></Icon>
