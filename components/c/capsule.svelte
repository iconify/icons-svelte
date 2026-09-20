<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmsy48vjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmsy48vjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:capsule" {...props}></Icon>
