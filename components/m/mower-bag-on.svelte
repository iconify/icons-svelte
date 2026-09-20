<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyu0hzd1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyu0hzd1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mower-bag-on" {...props}></Icon>
