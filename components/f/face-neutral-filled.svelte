<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l43uzl-6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l43uzl-6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:face-neutral-filled" {...props}></Icon>
