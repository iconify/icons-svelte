<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_vtj1bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_vtj1bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:logmein-logo-2-solid" {...props}></Icon>
