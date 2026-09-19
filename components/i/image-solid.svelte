<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inf1nzbws.css';
import '../../css/m/mjeguwb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inf1nzbws"/><path class="mjeguwb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:image-solid" {...props}></Icon>
