<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1-n19beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1-n19beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:menu-sharp-duotone" {...props}></Icon>
