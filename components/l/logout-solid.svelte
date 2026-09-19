<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4nt_319i.css';
import '../../css/a/ac_y-5bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4nt_319i"/><path class="ac_y-5bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:logout-solid" {...props}></Icon>
