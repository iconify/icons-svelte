<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/p/pb418gb3z.css';
import '../../css/q/q-c3nrjwl.css';
import '../../css/k/k7vaebzuk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUrLoXbLe"><g class="s9cl3zbei"><path class="pb418gb3z"/><path class="q-c3nrjwl"/><ellipse class="k7vaebzuk"/></g></mask></defs><path mask="url(#SVGUrLoXbLe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:french-fries" {...props}></Icon>
