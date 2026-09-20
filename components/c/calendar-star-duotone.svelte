<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmunasb2f.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/m/mnr4ubw3e.css';
import '../../css/f/fzydk7e5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmunasb2f"/><g class="xtpeb-edw"><path clip-rule="evenodd" class="mnr4ubw3e"/><path class="fzydk7e5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-star-duotone" {...props}></Icon>
