<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s85a2nbxa.css';
import '../../css/m/mnmkzno2m.css';
import '../../css/w/wa-w08h6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s85a2nbxa"/><path class="mnmkzno2m"/><path class="wa-w08h6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paper-bag-duotone" {...props}></Icon>
