<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv8-yz4el.css';
import '../../css/j/jvw8zwcpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8-yz4el"/><path clip-rule="evenodd" class="jvw8zwcpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-triangle-light" {...props}></Icon>
