<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lelswbxrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lelswbxrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-cog-sharp-fill" {...props}></Icon>
