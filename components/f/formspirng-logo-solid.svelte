<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obxlh5k_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obxlh5k_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:formspirng-logo-solid" {...props}></Icon>
