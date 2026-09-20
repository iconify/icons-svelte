<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv5m0ubjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv5m0ubjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plane-landing-sharp" {...props}></Icon>
