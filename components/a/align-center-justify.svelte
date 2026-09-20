<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qipzo4amq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qipzo4amq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align-center-justify" {...props}></Icon>
