<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/z5mka_22y.css';
import '../../css/y/yqkq0p36x.css';
import '../../css/i/i4wkegb-l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiDQMqbhV"><g class="v3_i3wktz"><path class="z5mka_22y"/><path class="yqkq0p36x"/><path class="i4wkegb-l"/></g></mask></defs><path mask="url(#SVGiDQMqbhV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:mail" {...props}></Icon>
