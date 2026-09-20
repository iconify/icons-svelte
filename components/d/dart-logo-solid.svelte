<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vurxy5g5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vurxy5g5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dart-logo-solid" {...props}></Icon>
