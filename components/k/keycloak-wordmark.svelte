<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsuy9zbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rsuy9zbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:keycloak-wordmark" {...props}></Icon>
