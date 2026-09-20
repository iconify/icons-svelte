<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x03bb4t8g.css';
import '../../css/k/k-_e98l6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="x03bb4t8g"/><path class="k-_e98l6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:adobe-illustrator" {...props}></Icon>
