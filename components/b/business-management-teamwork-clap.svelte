<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yolsd6bcj.css';
import '../../css/i/ir84fxbty.css';
import '../../css/v/vzf5asbos.css';
import '../../css/k/ks79mxcop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yolsd6bcj"/><path class="ir84fxbty"/><path class="vzf5asbos"/><path class="ks79mxcop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-management-teamwork-clap" {...props}></Icon>
