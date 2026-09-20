<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m10uxt63m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m10uxt63m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:edgeless" {...props}></Icon>
