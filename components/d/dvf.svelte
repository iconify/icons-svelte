<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy5h9y4sa.css';
import '../../css/n/nzkrizz9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy5h9y4sa"/><path clip-rule="evenodd" class="nzkrizz9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dvf" {...props}></Icon>
