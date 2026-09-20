<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1jojacbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1jojacbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-2-fill" {...props}></Icon>
