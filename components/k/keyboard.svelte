<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uplqc902i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uplqc902i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:keyboard" {...props}></Icon>
