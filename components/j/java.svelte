<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1jzwzbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1jzwzbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:java" {...props}></Icon>
