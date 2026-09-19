<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g88ua1b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g88ua1b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:doube-window-l-open" {...props}></Icon>
