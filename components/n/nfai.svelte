<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oho6lgbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oho6lgbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nfai" {...props}></Icon>
