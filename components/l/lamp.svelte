<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o39tw9d9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o39tw9d9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:lamp" {...props}></Icon>
