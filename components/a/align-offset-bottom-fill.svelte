<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe8kw5b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe8kw5b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-bottom-fill" {...props}></Icon>
