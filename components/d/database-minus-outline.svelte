<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqavzjbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqavzjbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-minus-outline" {...props}></Icon>
