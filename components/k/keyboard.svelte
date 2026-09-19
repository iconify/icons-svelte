<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/arj7difgh.css';
import '../../css/d/d9n_kpbfh.css';
import '../../css/n/n08b62aoj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQPlCdath"><g class="ft5dv1b6b"><path class="arj7difgh"/><path clip-rule="evenodd" class="d9n_kpbfh"/><path class="n08b62aoj"/></g></mask></defs><path mask="url(#SVGQPlCdath)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:keyboard" {...props}></Icon>
