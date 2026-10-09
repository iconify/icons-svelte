<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xujk5fdpi.css';
import '../../css/x/x1dswctxk.css';
import '../../css/z/zjk_4wbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xujk5fdpi"/><path class="x1dswctxk"/><path class="zjk_4wbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-truck-48" {...props}></Icon>
