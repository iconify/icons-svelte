<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk65fkbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk65fkbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clapperboard-filled" {...props}></Icon>
