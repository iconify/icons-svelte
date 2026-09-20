<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-ihcm2lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-ihcm2lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:android-phone-slash" {...props}></Icon>
