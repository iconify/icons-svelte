<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/y/y9u401bey.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3f9NbehH"><g class="wwvp95byt"><rect class="g47cb4b4t"/><path class="y9u401bey"/></g></mask></defs><path mask="url(#SVG3f9NbehH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:chinese-one" {...props}></Icon>
