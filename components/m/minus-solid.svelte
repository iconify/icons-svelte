<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjc2acbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjc2acbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:minus-solid" {...props}></Icon>
