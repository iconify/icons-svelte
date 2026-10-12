<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj2squb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj2squb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:anvil-filled" {...props}></Icon>
