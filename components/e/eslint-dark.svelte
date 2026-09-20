<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_e-ddbdl.css';
import '../../css/d/dj5rh1r0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":324,"height":285.096};
const content = `<path class="b_e-ddbdl"/><path class="dj5rh1r0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eslint-dark" {...props}></Icon>
