<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muui0pbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muui0pbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-6-sharp" {...props}></Icon>
