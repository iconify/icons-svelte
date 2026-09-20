<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwqioovyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwqioovyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-multiple-blank-fill" {...props}></Icon>
