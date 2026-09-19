<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phes-ab4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phes-ab4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:opnsense" {...props}></Icon>
