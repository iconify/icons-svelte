<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk_47gbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_47gbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lightbulb-sharp" {...props}></Icon>
