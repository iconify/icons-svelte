<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnlwwnn0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnlwwnn0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:application-add-solid" {...props}></Icon>
