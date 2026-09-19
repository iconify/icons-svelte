<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smh9_eb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smh9_eb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:radio" {...props}></Icon>
