<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga5op1ncr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ga5op1ncr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-lines-solid" {...props}></Icon>
