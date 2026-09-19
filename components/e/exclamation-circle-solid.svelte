<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev7dl1b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ev7dl1b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:exclamation-circle-solid" {...props}></Icon>
