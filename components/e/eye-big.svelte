<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aps6ewwol.css';
import '../../css/d/dno86xatc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aps6ewwol"/><path class="dno86xatc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eye-big" {...props}></Icon>
