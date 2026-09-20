<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyrsscxbi.css';
import '../../css/p/pha2jnncv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyrsscxbi"/><path class="pha2jnncv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:insur" {...props}></Icon>
