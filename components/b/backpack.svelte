<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmci96b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmci96b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:backpack" {...props}></Icon>
