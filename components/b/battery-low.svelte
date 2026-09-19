<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsjttz3bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsjttz3bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:battery-low" {...props}></Icon>
