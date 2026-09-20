<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9bmeds-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9bmeds-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-o-solid" {...props}></Icon>
