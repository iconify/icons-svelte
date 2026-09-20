<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0056zbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0056zbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:quote" {...props}></Icon>
