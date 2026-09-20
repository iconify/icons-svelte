<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3zz_pb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3zz_pb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-add-fill" {...props}></Icon>
