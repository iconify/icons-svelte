<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nmhlnubfi.css';
import '../../css/e/eyrri5bfj.css';
import '../../css/u/u6ja47b5r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8Lj3pb0C"><g class="ft5dv1b6b"><path class="nmhlnubfi"/><path clip-rule="evenodd" class="eyrri5bfj"/><path class="u6ja47b5r"/></g></mask></defs><path mask="url(#SVG8Lj3pb0C)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:people-plus" {...props}></Icon>
