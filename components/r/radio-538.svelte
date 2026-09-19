<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ronw7myve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ronw7myve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:radio-538" {...props}></Icon>
