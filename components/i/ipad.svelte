<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b7c5wh5qe.css';
import '../../css/o/o5hmfpl1w.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeATNtgLq"><g class="s9cl3zbei"><rect class="b7c5wh5qe"/><path class="o5hmfpl1w"/></g></mask></defs><path mask="url(#SVGeATNtgLq)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ipad" {...props}></Icon>
