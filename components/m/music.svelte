<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ntry5bc5r.css';
import '../../css/y/ybrt331fk.css';
import '../../css/d/d6vn-ssir.css';
import '../../css/q/qoyancbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="ntry5bc5r"/><circle class="ybrt331fk"/><path class="d6vn-ssir"/><path class="qoyancbha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:music" {...props}></Icon>
