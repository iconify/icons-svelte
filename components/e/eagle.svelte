<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xcl6nbhkj.css';
import '../../css/v/vlzbjhbij.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb6KAzcRO"><g class="ft5dv1b6b"><path class="xcl6nbhkj"/><circle class="vlzbjhbij"/></g></mask></defs><path mask="url(#SVGb6KAzcRO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:eagle" {...props}></Icon>
