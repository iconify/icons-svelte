<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrmll9g5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrmll9g5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-right-sharp" {...props}></Icon>
