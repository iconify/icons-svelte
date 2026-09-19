<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/n/ngt05uq9h.css';
import '../../css/f/fwohfu3-q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrTRund7K"><g class="gopnm44um"><path clip-rule="evenodd" class="ngt05uq9h"/><path class="fwohfu3-q"/></g></mask></defs><path mask="url(#SVGrTRund7K)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:inner-shadow-up" {...props}></Icon>
