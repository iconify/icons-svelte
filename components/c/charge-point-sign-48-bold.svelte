<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs_4a5yyu.css';
import '../../css/z/zetb63f3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rs_4a5yyu"/><path class="zetb63f3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charge-point-sign-48-bold" {...props}></Icon>
