<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/khaj5_bao.css';
import '../../css/q/qm5u6kboc.css';
import '../../css/j/jfg1lmblt.css';
import '../../css/t/tw64bqv6e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzamU61cz"><g class="aql7dnt-u"><path class="khaj5_bao"/><path class="qm5u6kboc"/><path class="jfg1lmblt"/><path class="tw64bqv6e"/></g></mask></defs><path mask="url(#SVGzamU61cz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:milk-one" {...props}></Icon>
