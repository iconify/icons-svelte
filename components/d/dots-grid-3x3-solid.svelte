<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/j/jygyqc4qd.css';
import '../../css/y/ys9zrsb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path clip-rule="evenodd" class="jygyqc4qd"/><path class="ys9zrsb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:dots-grid-3x3-solid" {...props}></Icon>
