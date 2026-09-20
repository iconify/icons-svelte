<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tweml3g7s.css';
import '../../css/s/sk9-dtbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tweml3g7s"/><path clip-rule="evenodd" class="sk9-dtbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:info-32" {...props}></Icon>
