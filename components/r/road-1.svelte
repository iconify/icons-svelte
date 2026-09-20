<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl6h39t1z.css';
import '../../css/b/b9iubibxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl6h39t1z"/><path clip-rule="evenodd" class="b9iubibxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:road-1" {...props}></Icon>
