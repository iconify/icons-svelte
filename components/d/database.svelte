<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/to71q5bap.css';
import '../../css/k/kz-auxbsw.css';
import '../../css/d/d84f9nr-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="to71q5bap"/><path class="kz-auxbsw"/><path class="d84f9nr-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:database" {...props}></Icon>
