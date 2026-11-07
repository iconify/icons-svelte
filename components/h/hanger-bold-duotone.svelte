<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0q8p-bqq.css';
import '../../css/n/n5-1bobdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0q8p-bqq"/><path class="n5-1bobdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hanger-bold-duotone" {...props}></Icon>
