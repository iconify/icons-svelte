<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbue6y19c.css';
import '../../css/h/hcbo7lb7t.css';
import '../../css/j/j-sz-bc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lbue6y19c"/><path class="hcbo7lb7t"/><circle class="j-sz-bc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:git-cliff" {...props}></Icon>
