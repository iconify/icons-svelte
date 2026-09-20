<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3sk6hbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3sk6hbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:receipt-text" {...props}></Icon>
