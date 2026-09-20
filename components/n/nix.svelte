<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au6clhbxu.css';
import '../../css/c/cpvng1bhd.css';
import '../../css/n/nbpor1b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<g class="au6clhbxu"><path class="cpvng1bhd"/><path class="nbpor1b9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nix" {...props}></Icon>
