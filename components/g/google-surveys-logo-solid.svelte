<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoha7p_ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eoha7p_ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-surveys-logo-solid" {...props}></Icon>
