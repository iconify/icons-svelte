<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu-6g1b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu-6g1b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:radarr" {...props}></Icon>
