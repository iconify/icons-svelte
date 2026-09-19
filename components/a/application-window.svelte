<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb784wbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb784wbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:application-window" {...props}></Icon>
