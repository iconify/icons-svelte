<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ldfj9ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="n_ldfj9ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:picnic-site-11" {...props}></Icon>
