<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n0y6j6byu.css';
import '../../css/f/fiyr8cb9q.css';
import '../../css/y/yimcpzbjq.css';
import '../../css/k/k2a0vobbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n0y6j6byu"/><path class="fiyr8cb9q"/><path class="yimcpzbjq"/><path class="k2a0vobbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:help-headphones-customer-support-human" {...props}></Icon>
