<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_24aebhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_24aebhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:raindrops-alt" {...props}></Icon>
