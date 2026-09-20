<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn12tg0us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn12tg0us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-edit-line" {...props}></Icon>
