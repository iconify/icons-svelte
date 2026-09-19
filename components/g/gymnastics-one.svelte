<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgga7abld.css';
import '../../css/p/p9pavjj4d.css';
import '../../css/l/ln6f3q98l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvq32Ydak"><g class="cgga7abld"><path class="p9pavjj4d"/><path class="ln6f3q98l"/></g></mask></defs><path mask="url(#SVGvq32Ydak)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:gymnastics-one" {...props}></Icon>
