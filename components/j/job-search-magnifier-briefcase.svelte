<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/epuchabnl.css';
import '../../css/h/h22qwyaft.css';
import '../../css/u/uxo8fdb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="epuchabnl"/><path class="h22qwyaft"/><path class="uxo8fdb3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:job-search-magnifier-briefcase" {...props}></Icon>
