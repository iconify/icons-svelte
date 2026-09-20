<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-o9xacme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-o9xacme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:folder-block-solid" {...props}></Icon>
