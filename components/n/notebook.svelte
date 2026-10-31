<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gkdbr3bax.css';
import '../../css/p/pmmuggidj.css';
import '../../css/u/ug-wd558g.css';
import '../../css/a/ajwrlub9f.css';
import '../../css/o/o9hb7faeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gkdbr3bax wm-k"/><path class="pmmuggidj wm-shine"/><path class="ug-wd558g wm-shine"/><path class="ajwrlub9f wm-shine"/><path class="o9hb7faeo wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:notebook" {...props}></Icon>
