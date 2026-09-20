<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrz8h778r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrz8h778r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:archive-box-solid" {...props}></Icon>
