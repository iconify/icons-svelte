<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepvz7i-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pepvz7i-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-up" {...props}></Icon>
