<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9zfudblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9zfudblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:buttons-all-flat" {...props}></Icon>
