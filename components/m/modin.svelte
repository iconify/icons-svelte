<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjlbo5axu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjlbo5axu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:modin" {...props}></Icon>
