<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3wltllsx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdXZvgbiJ"><path class="x3wltllsx"/></mask></defs><path mask="url(#SVGdXZvgbiJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-one" {...props}></Icon>
