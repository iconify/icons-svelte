<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/w/wac_9cbmb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwHeP2bzv"><g class="wwvp95byt"><rect class="g47cb4b4t"/><path class="wac_9cbmb"/></g></mask></defs><path mask="url(#SVGwHeP2bzv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:asterisk-key" {...props}></Icon>
