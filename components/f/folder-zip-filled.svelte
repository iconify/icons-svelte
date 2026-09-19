<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3t8n_b1o.css';
import '../../css/j/jit9i0epo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3t8n_b1o"/><path class="jit9i0epo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-zip-filled" {...props}></Icon>
