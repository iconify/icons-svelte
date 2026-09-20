<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ush94023r.css';
import '../../css/l/lb-bssbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ush94023r"/><path class="lb-bssbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-24" {...props}></Icon>
