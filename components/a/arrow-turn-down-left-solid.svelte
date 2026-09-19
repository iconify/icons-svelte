<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ev7zbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e8ev7zbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-down-left-solid" {...props}></Icon>
