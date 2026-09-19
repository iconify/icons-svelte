<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyykyh0ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tyykyh0ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-check-filled" {...props}></Icon>
