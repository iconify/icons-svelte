<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyqotpbcg.css';
import '../../css/a/aqfpmgb6v.css';
import '../../css/g/ghb7ubbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lyqotpbcg"><rect class="aqfpmgb6v"/><path class="ghb7ubbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:mic-duotone" {...props}></Icon>
