<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjaa7tbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjaa7tbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:leanpub" {...props}></Icon>
