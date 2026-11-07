<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq2hqvwyz.css';
import '../../css/b/b9htj9b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq2hqvwyz"/><path class="b9htj9b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-output-bold-duotone" {...props}></Icon>
