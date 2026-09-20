<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j80ujrauk.css';
import '../../css/q/qsvb7nb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j80ujrauk"/><path class="qsvb7nb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:building-3-filled" {...props}></Icon>
