<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5wow2bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5wow2bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-arrow-down" {...props}></Icon>
