<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pmwdljh8p.css';
import '../../css/g/gaqp2k4re.css';
import '../../css/k/kac42ebbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pmwdljh8p"/><path class="gaqp2k4re"/><path class="kac42ebbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-database" {...props}></Icon>
