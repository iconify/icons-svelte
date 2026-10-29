<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/typ168lje.css';
import '../../css/b/brefaib6f.css';
import '../../css/g/gv1maybhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="typ168lje wm-shadow"/><path class="brefaib6f wm-k"/><path class="gv1maybhe wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:maximize" {...props}></Icon>
