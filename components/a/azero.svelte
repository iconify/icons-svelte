<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9ei7tbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v9ei7tbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:azero" {...props}></Icon>
