<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr03y7bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr03y7bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-9-fill" {...props}></Icon>
