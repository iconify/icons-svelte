<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny-3uobra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ny-3uobra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:clipboard-16-solid" {...props}></Icon>
