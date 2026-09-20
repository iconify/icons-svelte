<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb0b6ubgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hb0b6ubgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kibana-logo-block" {...props}></Icon>
