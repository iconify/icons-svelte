<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fp5w7jz8b.css';
import '../../css/k/kwjjqxyvb.css';
import '../../css/g/gpggdbcsk.css';
import '../../css/c/c2nhh94oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fp5w7jz8b"/><path class="kwjjqxyvb"/><path class="gpggdbcsk"/><path class="c2nhh94oa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:disability-hearing-t" {...props}></Icon>
