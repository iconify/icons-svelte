<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ta8tb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ta8tb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-fill" {...props}></Icon>
