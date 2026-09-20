<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwrs0eqor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwrs0eqor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kakao" {...props}></Icon>
