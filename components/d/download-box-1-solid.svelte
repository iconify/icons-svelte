<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soq9mxeph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="soq9mxeph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:download-box-1-solid" {...props}></Icon>
