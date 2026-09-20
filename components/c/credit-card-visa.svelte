<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/me4zmhbqc.css';
import '../../css/k/khq3t1zcp.css';
import '../../css/e/erc7edbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="me4zmhbqc"/><path class="khq3t1zcp"/><path class="erc7edbxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:credit-card-visa" {...props}></Icon>
