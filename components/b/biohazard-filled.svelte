<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm7p5zbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm7p5zbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:biohazard-filled" {...props}></Icon>
