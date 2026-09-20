<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q9pojxb5k.css';
import '../../css/e/endhulb8v.css';
import '../../css/q/qcfv3sa_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q9pojxb5k"/><path class="endhulb8v"/><path class="qcfv3sa_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:mobilephone-action-settings" {...props}></Icon>
