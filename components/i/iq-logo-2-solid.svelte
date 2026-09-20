<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdu3yp8fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdu3yp8fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iq-logo-2-solid" {...props}></Icon>
