<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsrb3dbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsrb3dbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:download-stack-solid" {...props}></Icon>
