<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrg2u5bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrg2u5bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:binoculars-filled" {...props}></Icon>
