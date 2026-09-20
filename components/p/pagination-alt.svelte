<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bxh-jdb5w.css';
import '../../css/v/vi04yvb6a.css';
import '../../css/d/d-u2_-1yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bxh-jdb5w"/><path class="vi04yvb6a"/><path class="d-u2_-1yy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pagination-alt" {...props}></Icon>
