<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a53go_wkz.css';
import '../../css/c/ck-pzhbhq.css';
import '../../css/c/c7gp0hbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a53go_wkz"/><path class="ck-pzhbhq"/><path class="c7gp0hbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mnd" {...props}></Icon>
