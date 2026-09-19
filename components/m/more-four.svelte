<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8-c1m0ua.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1RrlacnE"><path class="k8-c1m0ua"/></mask></defs><path mask="url(#SVG1RrlacnE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:more-four" {...props}></Icon>
