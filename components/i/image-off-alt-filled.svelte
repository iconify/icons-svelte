<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il0_djbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il0_djbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-off-alt-filled" {...props}></Icon>
