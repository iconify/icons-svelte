<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qllazcb1e.css';
import '../../css/c/cl0c6rbvl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDZfZBd9m"><g class="s9cl3zbei"><path clip-rule="evenodd" class="qllazcb1e"/><path class="cl0c6rbvl"/></g></mask></defs><path mask="url(#SVGDZfZBd9m)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:orthopedic" {...props}></Icon>
