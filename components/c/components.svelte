<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5qqsfbyd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGA4mOJdqT"><path class="n5qqsfbyd"/></mask></defs><path mask="url(#SVGA4mOJdqT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:components" {...props}></Icon>
