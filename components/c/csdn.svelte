<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v69l6yjwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v69l6yjwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:csdn" {...props}></Icon>
