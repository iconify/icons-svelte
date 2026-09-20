<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxchu0bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jxchu0bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:online-medical-service-monitor-remix" {...props}></Icon>
