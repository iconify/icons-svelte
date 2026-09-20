<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yjlbdu1jl.css';
import '../../css/f/fs3te152g.css';
import '../../css/o/o4ikk4n8i.css';
import '../../css/n/n78r9lbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yjlbdu1jl"/><path class="fs3te152g"/><path class="o4ikk4n8i"/><path class="n78r9lbcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:credit-card-smartphone" {...props}></Icon>
