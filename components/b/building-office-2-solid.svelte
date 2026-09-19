<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz35pabwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz35pabwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-office-2-solid" {...props}></Icon>
