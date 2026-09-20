<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q409n5tsy.css';
import '../../css/m/mi4ud5ykd.css';
import '../../css/l/lz8pembln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q409n5tsy"/><path class="mi4ud5ykd"/><path class="lz8pembln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-repository-private" {...props}></Icon>
