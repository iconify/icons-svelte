<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m40d-gbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m40d-gbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-ellipsis-filled" {...props}></Icon>
