<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/ytlnqnvjr.css';
import '../../css/i/izakys4nx.css';
import '../../css/o/o1e5bsb1v.css';
import '../../css/b/btuxjnb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="ytlnqnvjr"/><path vector-effect="non-scaling-stroke" class="izakys4nx"/><circle vector-effect="non-scaling-stroke" class="o1e5bsb1v"/><circle vector-effect="non-scaling-stroke" class="btuxjnb0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:reaction" {...props}></Icon>
