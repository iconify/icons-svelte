<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve0ei_2st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve0ei_2st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clock-play" {...props}></Icon>
