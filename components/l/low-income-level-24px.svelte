<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lpwj95bgh.css';
import '../../css/a/ayl8drpcr.css';
import '../../css/v/v4x6_8bfa.css';
import '../../css/y/yzwlj9a5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lpwj95bgh"/><path clip-rule="evenodd" class="ayl8drpcr"/><path class="v4x6_8bfa"/><path clip-rule="evenodd" class="yzwlj9a5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:low-income-level-24px" {...props}></Icon>
