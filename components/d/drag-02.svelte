<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peggr9bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peggr9bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:drag-02" {...props}></Icon>
