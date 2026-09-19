<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1b7dlb_x.css';
import '../../css/p/p586cjbdt.css';
import '../../css/o/owhr5ut9l.css';
import '../../css/j/jhszfhpco.css';
import '../../css/p/pl5pmnbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1b7dlb_x"/><path class="p586cjbdt"/><path class="owhr5ut9l"/><path class="jhszfhpco"/><path class="pl5pmnbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:datashare" {...props}></Icon>
