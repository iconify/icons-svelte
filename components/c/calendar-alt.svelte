<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c374pwbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c374pwbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:calendar-alt" {...props}></Icon>
