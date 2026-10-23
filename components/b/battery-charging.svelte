<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqn6nsbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqn6nsbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-charging" {...props}></Icon>
