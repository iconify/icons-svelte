<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpe0vbb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tpe0vbb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lightbulb-slash-fill" {...props}></Icon>
