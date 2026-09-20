<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4l_v6abs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4l_v6abs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:necktie-remix" {...props}></Icon>
