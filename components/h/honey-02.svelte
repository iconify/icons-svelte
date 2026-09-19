<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3cx9kfqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3cx9kfqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:honey-02" {...props}></Icon>
