<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9grasspe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9grasspe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-up-down-solid" {...props}></Icon>
