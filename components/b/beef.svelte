<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ykt5bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ykt5bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:beef" {...props}></Icon>
