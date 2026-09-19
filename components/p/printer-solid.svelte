<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr7eoibfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr7eoibfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:printer-solid" {...props}></Icon>
