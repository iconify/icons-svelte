<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq7etfk1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hq7etfk1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-read-filled" {...props}></Icon>
