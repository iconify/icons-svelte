<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nc0ss4key.css';
import '../../css/s/scuo7ib6n.css';
import '../../css/n/njqf7ab-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nc0ss4key"/><path class="scuo7ib6n"/><path class="njqf7ab-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:person-plus" {...props}></Icon>
