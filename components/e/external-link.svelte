<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mq7zwiqhb.css';
import '../../css/j/jl73e1lrn.css';
import '../../css/i/im8flh3ra.css';
import '../../css/y/yij8ymbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mq7zwiqhb wm-shadow"/><path class="jl73e1lrn wm-shadow"/><path class="im8flh3ra"/><path class="yij8ymbvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:external-link" {...props}></Icon>
