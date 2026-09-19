<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/afq7mjurd.css';
import '../../css/e/eiol0ep0o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHp2ribKM"><g class="v3_i3wktz"><path class="afq7mjurd"/><path class="eiol0ep0o"/></g></mask></defs><path mask="url(#SVGHp2ribKM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:phone-incoming" {...props}></Icon>
