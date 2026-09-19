<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr-61bb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr-61bb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:information-circle-solid" {...props}></Icon>
