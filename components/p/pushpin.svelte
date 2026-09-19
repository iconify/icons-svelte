<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j848glbsj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXXXG9bEB"><path class="j848glbsj"/></mask></defs><path mask="url(#SVGXXXG9bEB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pushpin" {...props}></Icon>
