<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iafigdn5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iafigdn5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roon" {...props}></Icon>
