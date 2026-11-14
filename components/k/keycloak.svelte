<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gciqwy85p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gciqwy85p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:keycloak" {...props}></Icon>
