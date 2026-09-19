<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yal-1qa0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yal-1qa0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pdf-file" {...props}></Icon>
