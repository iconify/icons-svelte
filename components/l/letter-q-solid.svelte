<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8ag3311v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ag3311v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-q-solid" {...props}></Icon>
