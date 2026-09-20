<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v041m5b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v041m5b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:add-and-subtract" {...props}></Icon>
