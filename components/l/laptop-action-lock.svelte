<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/no-cdxbss.css';
import '../../css/b/blqx9nbej.css';
import '../../css/e/ewa20qhlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="no-cdxbss"/><path class="blqx9nbej"/><path class="ewa20qhlh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:laptop-action-lock" {...props}></Icon>
