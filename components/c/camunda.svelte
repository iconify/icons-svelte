<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mldcbzlkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mldcbzlkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:camunda" {...props}></Icon>
