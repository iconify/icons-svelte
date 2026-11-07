<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4tjy3b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4tjy3b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-rounded-broken" {...props}></Icon>
