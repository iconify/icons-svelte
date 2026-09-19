<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsg_c7jms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsg_c7jms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-arrow-down-solid" {...props}></Icon>
