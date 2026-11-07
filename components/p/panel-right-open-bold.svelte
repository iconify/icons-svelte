<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7y90fksk.css';
import '../../css/d/dkbffkbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7y90fksk"/><path class="dkbffkbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-right-open-bold" {...props}></Icon>
