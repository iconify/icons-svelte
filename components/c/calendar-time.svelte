<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v2rwe_1tf.css';
import '../../css/o/oe0hep0lg.css';
import '../../css/s/s9jhijksu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v2rwe_1tf"/><path class="oe0hep0lg"/><path class="s9jhijksu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-time" {...props}></Icon>
