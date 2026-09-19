<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb-3bsb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb-3bsb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:captioning-solid" {...props}></Icon>
