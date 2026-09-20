<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukk_oybpm.css';
import '../../css/u/u-7z_t4fb.css';
import '../../css/v/v-q4e7xtu.css';
import '../../css/j/ju0jd-e1r.css';
import '../../css/u/us33y-a5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ukk_oybpm"/><path class="u-7z_t4fb"/><path class="v-q4e7xtu"/><path class="ju0jd-e1r"/><path class="us33y-a5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nps-enhanced-light" {...props}></Icon>
