<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-6rz8hpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-6rz8hpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:linksys" {...props}></Icon>
