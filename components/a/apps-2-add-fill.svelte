<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnz4es2ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnz4es2ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apps-2-add-fill" {...props}></Icon>
