<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h83px-b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h83px-b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-12-sharp" {...props}></Icon>
