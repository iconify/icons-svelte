<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o812x4bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="o812x4bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:message-alt-writing-f" {...props}></Icon>
