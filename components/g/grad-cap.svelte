<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8-kk1bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n8-kk1bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grad-cap" {...props}></Icon>
