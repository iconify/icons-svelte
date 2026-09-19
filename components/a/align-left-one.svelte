<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/z/zm1am8zwq.css';
import '../../css/g/ghilmzbaa.css';
import '../../css/a/a_66_cbsw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJQBRUoTK"><g class="hv130ab-t"><path class="zm1am8zwq"/><path class="ghilmzbaa"/><path class="a_66_cbsw"/></g></mask></defs><path mask="url(#SVGJQBRUoTK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:align-left-one" {...props}></Icon>
