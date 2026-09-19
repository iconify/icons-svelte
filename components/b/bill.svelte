<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/e/ebd6yeibc.css';
import '../../css/y/yj6rd0m8s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGie0JFcFo"><g class="wwvp95byt"><path class="ebd6yeibc"/><path class="yj6rd0m8s"/></g></mask></defs><path mask="url(#SVGie0JFcFo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bill" {...props}></Icon>
