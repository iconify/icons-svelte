<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apfv19-nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apfv19-nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rede-bandeirantes" {...props}></Icon>
