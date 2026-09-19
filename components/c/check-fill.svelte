<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdoxi1qjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdoxi1qjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:check-fill" {...props}></Icon>
