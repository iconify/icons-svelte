<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l95p6hgdb.css';
import '../../css/x/xea6o-oef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l95p6hgdb"/><path class="xea6o-oef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:photoshop" {...props}></Icon>
