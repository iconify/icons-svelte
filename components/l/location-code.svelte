<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbip4gbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbip4gbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-code" {...props}></Icon>
