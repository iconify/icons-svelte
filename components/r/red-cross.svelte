<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/m/mzszod_2j.css';
import '../../css/v/v0ki-vbca.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwywZYbqH"><g class="wwvp95byt"><circle class="mzszod_2j"/><path class="v0ki-vbca"/></g></mask></defs><path mask="url(#SVGwywZYbqH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:red-cross" {...props}></Icon>
