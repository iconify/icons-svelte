<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ubuf0l-kw.css';
import '../../css/h/h20pzcb1e.css';
import '../../css/e/e5e8fq4db.css';
import '../../css/m/mrk4qwc0c.css';
import '../../css/t/tcxxukgzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ubuf0l-kw wm-k"/><path class="h20pzcb1e wm-k"/><path class="e5e8fq4db wm-shadow"/><path class="mrk4qwc0c wm-shine"/><path class="tcxxukgzk wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-valentine:database" {...props}></Icon>
