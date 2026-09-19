<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqgh9acwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqgh9acwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:language-solid" {...props}></Icon>
