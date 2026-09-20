<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygc77k-_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygc77k-_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:brackets-curly" {...props}></Icon>
