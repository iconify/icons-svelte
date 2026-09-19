<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m088jbc1k.css';
import '../../css/o/osy329bko.css';
import '../../css/w/wd942qb8r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBnFofygF"><g class="s9cl3zbei"><path class="m088jbc1k"/><rect class="osy329bko"/><path class="wd942qb8r"/></g></mask></defs><path mask="url(#SVGBnFofygF)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:financing-two" {...props}></Icon>
