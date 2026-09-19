<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4nt_319i.css';
import '../../css/t/tv2_2htnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4nt_319i"/><path class="tv2_2htnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:login-solid" {...props}></Icon>
