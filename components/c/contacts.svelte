<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep8jf_6qd.css';
import '../../css/o/oh4ogzb0c.css';
import '../../css/e/e2kqkxb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep8jf_6qd"/><circle class="oh4ogzb0c"/><path class="e2kqkxb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:contacts" {...props}></Icon>
