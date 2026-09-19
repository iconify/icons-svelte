<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjl0uebbh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLXXc1GxT"><path class="yjl0uebbh"/></mask></defs><path mask="url(#SVGLXXc1GxT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bookshelf" {...props}></Icon>
