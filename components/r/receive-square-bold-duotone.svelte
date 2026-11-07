<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/g/g21do5pdv.css';
import '../../css/x/xx4egsacr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="g21do5pdv"/><path class="xx4egsacr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:receive-square-bold-duotone" {...props}></Icon>
