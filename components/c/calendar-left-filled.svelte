<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzhr5bbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzhr5bbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-left-filled" {...props}></Icon>
