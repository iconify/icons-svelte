<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at5new48p.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/g/gpvjwxk6r.css';
import '../../css/x/xxvql1bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle transform="translate(46.558 26.92)scale(3.04614)" class="at5new48p"/><g transform="translate(-3.216 -3.216)scale(1.09)" class="sxsjrzbyv"><path class="gpvjwxk6r"/><circle transform="translate(45.78 27.64)scale(2.795)" class="xxvql1bwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:circled-m" {...props}></Icon>
