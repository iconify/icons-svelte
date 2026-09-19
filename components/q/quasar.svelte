<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwxd6gr7h.css';
import '../../css/g/g-drd0b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bwxd6gr7h"/><path class="g-drd0b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:quasar" {...props}></Icon>
