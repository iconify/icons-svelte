<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kszgb5bkw.css';
import '../../css/x/x0man4b4w.css';
import '../../css/x/xcr_i7b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="kszgb5bkw"/><path class="x0man4b4w"/><path class="xcr_i7b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:aland-islands" {...props}></Icon>
