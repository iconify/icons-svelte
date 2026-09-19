<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qek2tkbit.css';
import '../../css/n/n6tabbcyg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0n4yUdds"><g class="s9cl3zbei"><rect class="qek2tkbit"/><path class="n6tabbcyg"/></g></mask></defs><path mask="url(#SVG0n4yUdds)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:eight-key" {...props}></Icon>
