<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_1d1rbat.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9H518cyu"><path class="o_1d1rbat"/></mask></defs><path mask="url(#SVG9H518cyu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:book-open" {...props}></Icon>
