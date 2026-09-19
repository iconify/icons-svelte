<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/l3gq4rh3k.css';
import '../../css/p/pfos4ebhf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaYjRbdkO"><g class="v3_i3wktz"><path class="l3gq4rh3k"/><path class="pfos4ebhf"/></g></mask></defs><path mask="url(#SVGaYjRbdkO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:fork" {...props}></Icon>
