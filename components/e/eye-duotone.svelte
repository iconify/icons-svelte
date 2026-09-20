<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wmcw7kbju.css';
import '../../css/x/xt31cgyzz.css';
import '../../css/k/kjbt3bbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wmcw7kbju"/><path class="xt31cgyzz"/><circle class="kjbt3bbno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:eye-duotone" {...props}></Icon>
