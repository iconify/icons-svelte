<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es3s4jbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es3s4jbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jira" {...props}></Icon>
