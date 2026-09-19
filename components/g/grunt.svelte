<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czzfe_76l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="czzfe_76l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:grunt" {...props}></Icon>
