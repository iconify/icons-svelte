<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc09--5dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jc09--5dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-woff" {...props}></Icon>
