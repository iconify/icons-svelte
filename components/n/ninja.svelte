<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg78mjbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg78mjbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ninja" {...props}></Icon>
