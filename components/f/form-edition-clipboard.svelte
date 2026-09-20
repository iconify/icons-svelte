<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sczk89p9c.css';
import '../../css/h/hu7lz1x8l.css';
import '../../css/w/w493op95g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sczk89p9c"/><path class="hu7lz1x8l"/><path class="w493op95g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:form-edition-clipboard" {...props}></Icon>
