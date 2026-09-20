<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvkz5rbsj.css';
import '../../css/h/hzy4kud9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvkz5rbsj"/><path class="hzy4kud9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-circle-right" {...props}></Icon>
