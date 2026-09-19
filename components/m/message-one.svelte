<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/h/h3mxyjh3o.css';
import '../../css/t/t43uemldg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWCI2renM"><g class="gopnm44um"><path class="h3mxyjh3o"/><path class="t43uemldg"/></g></mask></defs><path mask="url(#SVGWCI2renM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:message-one" {...props}></Icon>
