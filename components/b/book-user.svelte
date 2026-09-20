<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r0vgt4upi.css';
import '../../css/o/ot8yzyb7e.css';
import '../../css/p/ptvu1u_4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0vgt4upi"/><path class="ot8yzyb7e"/><circle class="ptvu1u_4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-user" {...props}></Icon>
