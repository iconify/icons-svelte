<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t68yh9beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t68yh9beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nest-wifi-logo-solid" {...props}></Icon>
