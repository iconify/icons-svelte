<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igizkkbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="igizkkbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:manjaro-logo-solid" {...props}></Icon>
