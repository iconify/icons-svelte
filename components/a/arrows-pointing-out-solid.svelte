<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pla8b4b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pla8b4b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-out-solid" {...props}></Icon>
