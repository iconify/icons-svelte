<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfxi5bcqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfxi5bcqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dishwasher-salt" {...props}></Icon>
