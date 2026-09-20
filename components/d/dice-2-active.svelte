<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy-z_rbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gy-z_rbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-2-active" {...props}></Icon>
