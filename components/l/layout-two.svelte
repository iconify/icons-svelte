<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/e/e5spbgbvw.css';
import '../../css/d/dav0ieqlc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQxVk0bOZ"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="e5spbgbvw"/><path class="dav0ieqlc"/></g></mask></defs><path mask="url(#SVGQxVk0bOZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:layout-two" {...props}></Icon>
