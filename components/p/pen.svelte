<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsxx68wym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsxx68wym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:pen" {...props}></Icon>
