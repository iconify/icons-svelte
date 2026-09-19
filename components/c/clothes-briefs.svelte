<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en2ec-blp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzzFfQcsj"><path class="en2ec-blp"/></mask></defs><path mask="url(#SVGzzFfQcsj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:clothes-briefs" {...props}></Icon>
