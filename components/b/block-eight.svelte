<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk83epm5a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2iNRAbJY"><path class="xk83epm5a"/></mask></defs><path mask="url(#SVG2iNRAbJY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-eight" {...props}></Icon>
