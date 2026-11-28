<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh0q-lilg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh0q-lilg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pull-request" {...props}></Icon>
