<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1crshb5u.css';
import '../../css/s/sihn2yb6f.css';
import '../../css/h/hk3z8gb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h1crshb5u"/><circle class="sihn2yb6f"/><circle class="hk3z8gb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:root-open" {...props}></Icon>
