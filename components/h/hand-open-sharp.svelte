<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psvuoo1mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psvuoo1mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-open-sharp" {...props}></Icon>
