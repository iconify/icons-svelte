<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaiyq5bvp.css';
import '../../css/y/yojx2obqy.css';
import '../../css/y/y9hdzabck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="yojx2obqy"/><path class="y9hdzabck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:coffeescript" {...props}></Icon>
