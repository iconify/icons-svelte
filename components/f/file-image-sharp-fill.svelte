<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia5_8rbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia5_8rbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-image-sharp-fill" {...props}></Icon>
