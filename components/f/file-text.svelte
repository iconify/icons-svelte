<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f6q5qubpi.css';
import '../../css/q/qmhvixbvw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDOBgedNx"><g class="aql7dnt-u"><path class="f6q5qubpi"/><path class="qmhvixbvw"/></g></mask></defs><path mask="url(#SVGDOBgedNx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:file-text" {...props}></Icon>
