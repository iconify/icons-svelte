<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da-mhk6xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da-mhk6xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:open-in-new" {...props}></Icon>
