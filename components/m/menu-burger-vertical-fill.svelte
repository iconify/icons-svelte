<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8605ubjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8605ubjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-vertical-fill" {...props}></Icon>
