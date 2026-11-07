<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdva5qsyp.css';
import '../../css/j/jwcaxlbam.css';
import '../../css/k/kll7rqb_y.css';
import '../../css/z/zpih-bbov.css';
import '../../css/t/t5k-_f5ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdva5qsyp"/><path class="jwcaxlbam"/><path class="kll7rqb_y"/><path class="zpih-bbov"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-square-2-outline" {...props}></Icon>
