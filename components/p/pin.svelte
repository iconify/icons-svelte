<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9-dmt_9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9-dmt_9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pin" {...props}></Icon>
