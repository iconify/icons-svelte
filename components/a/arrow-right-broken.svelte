<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfg6wabjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfg6wabjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-broken" {...props}></Icon>
