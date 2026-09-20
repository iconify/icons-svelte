<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpf30lb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpf30lb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:input-field" {...props}></Icon>
