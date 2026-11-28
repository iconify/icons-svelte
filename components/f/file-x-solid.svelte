<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps7ury_is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps7ury_is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-x-solid" {...props}></Icon>
