<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng5pp8tbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng5pp8tbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:eye-off" {...props}></Icon>
