<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o001ofuzg.css';
import '../../css/g/gv-7r_ppm.css';
import '../../css/p/pwrb__blp.css';
import '../../css/h/hefxuppcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o001ofuzg"/><path class="gv-7r_ppm"/><path class="pwrb__blp"/><path class="hefxuppcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cottage-48" {...props}></Icon>
