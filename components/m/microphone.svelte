<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h62f4pbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h62f4pbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:microphone" {...props}></Icon>
