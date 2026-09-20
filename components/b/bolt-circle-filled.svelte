<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m899ykb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m899ykb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bolt-circle-filled" {...props}></Icon>
