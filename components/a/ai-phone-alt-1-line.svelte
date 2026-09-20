<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h389tou-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h389tou-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-phone-alt-1-line" {...props}></Icon>
