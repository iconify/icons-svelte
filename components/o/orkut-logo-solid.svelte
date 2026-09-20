<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6vuzqbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6vuzqbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:orkut-logo-solid" {...props}></Icon>
