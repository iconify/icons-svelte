<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v174fl17m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v174fl17m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:flag-solid" {...props}></Icon>
