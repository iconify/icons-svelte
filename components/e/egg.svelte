<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/dvcapvbcu.css';
import '../../css/n/n3y4iwy_t.css';
import '../../css/s/szdnrl1jv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEhaW4dLm"><g class="s9cl3zbei"><circle class="dvcapvbcu"/><path class="n3y4iwy_t"/><path class="szdnrl1jv"/></g></mask></defs><path mask="url(#SVGEhaW4dLm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:egg" {...props}></Icon>
