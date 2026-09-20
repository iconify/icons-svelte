<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n7u4o-vzj.css';
import '../../css/l/lqjiyubml.css';
import '../../css/o/o-fe66dks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n7u4o-vzj"/><path class="lqjiyubml"/><path class="o-fe66dks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:laundry-hand-wash" {...props}></Icon>
