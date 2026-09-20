<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk5yd9wru.css';
import '../../css/y/ygr19icki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dk5yd9wru"/><path clip-rule="evenodd" class="ygr19icki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-start-16" {...props}></Icon>
