<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_7cduu4i.css';
import '../../css/x/xu6tp6cqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_7cduu4i"/><path class="xu6tp6cqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lungs" {...props}></Icon>
