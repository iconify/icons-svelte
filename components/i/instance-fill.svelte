<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c65f93b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c65f93b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:instance-fill" {...props}></Icon>
