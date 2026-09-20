<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn-j478mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn-j478mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ggp" {...props}></Icon>
