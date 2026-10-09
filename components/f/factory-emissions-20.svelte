<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emlsrnxct.css';
import '../../css/w/w80nymbio.css';
import '../../css/i/io7sfnrdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emlsrnxct"/><path class="w80nymbio"/><path class="io7sfnrdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:factory-emissions-20" {...props}></Icon>
