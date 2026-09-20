<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6c_nwb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6c_nwb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:file-fill" {...props}></Icon>
