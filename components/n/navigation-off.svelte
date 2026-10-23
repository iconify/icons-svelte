<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzze5nbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzze5nbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:navigation-off" {...props}></Icon>
