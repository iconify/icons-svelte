<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meyqr7u7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meyqr7u7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cloud-upload-solid" {...props}></Icon>
