<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4tmepvdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4tmepvdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-add" {...props}></Icon>
