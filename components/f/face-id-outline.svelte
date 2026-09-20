<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjwu3kbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qjwu3kbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:face-id-outline" {...props}></Icon>
