<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-g8xbcas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-g8xbcas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-left-solid" {...props}></Icon>
