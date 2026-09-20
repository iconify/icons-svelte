<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_aablbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_aablbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:maximize-2-sharp" {...props}></Icon>
