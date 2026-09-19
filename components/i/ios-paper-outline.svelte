<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8ruyacxf.css';
import '../../css/l/la4b0i5sl.css';
import '../../css/g/gx-o-jbfy.css';
import '../../css/b/b701h2wuj.css';
import '../../css/g/gb9s77bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8ruyacxf"/><path class="la4b0i5sl"/><path class="gx-o-jbfy"/><path class="b701h2wuj"/><path class="gb9s77bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-paper-outline" {...props}></Icon>
