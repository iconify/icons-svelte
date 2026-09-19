<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/zvkp0cb3v.css';
import '../../css/h/h1rmlkb4z.css';
import '../../css/s/so9--0nkn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5q5zqbWl"><g class="v3_i3wktz"><path class="zvkp0cb3v"/><path class="h1rmlkb4z"/><path class="so9--0nkn"/></g></mask></defs><path mask="url(#SVG5q5zqbWl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:aperture-priority" {...props}></Icon>
