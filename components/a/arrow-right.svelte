<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg_0asz9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg_0asz9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-right" {...props}></Icon>
