<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y21npvxed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y21npvxed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:image-highlights-solid" {...props}></Icon>
