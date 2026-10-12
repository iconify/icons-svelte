<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w717xbb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w717xbb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:beaker-filled" {...props}></Icon>
