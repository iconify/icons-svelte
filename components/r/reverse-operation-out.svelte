<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/c/cej2n11nh.css';
import '../../css/g/g03ocyb3a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaRRqpcCp"><g class="wwvp95byt"><path class="cej2n11nh"/><path class="g03ocyb3a"/></g></mask></defs><path mask="url(#SVGaRRqpcCp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:reverse-operation-out" {...props}></Icon>
