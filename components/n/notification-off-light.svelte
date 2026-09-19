<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rbns1x26b.css';
import '../../css/u/umzj1472b.css';
import '../../css/b/bg3j-3buk.css';
import '../../css/g/gq0qt0sbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rbns1x26b"/><circle class="umzj1472b"/><path class="bg3j-3buk"/><path class="gq0qt0sbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:notification-off-light" {...props}></Icon>
