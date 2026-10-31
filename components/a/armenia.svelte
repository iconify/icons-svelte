<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufvrkebxw.css';
import '../../css/o/owp3yfbrj.css';
import '../../css/v/v4iawlr0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ufvrkebxw"/><path class="owp3yfbrj"/><path class="v4iawlr0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:armenia" {...props}></Icon>
