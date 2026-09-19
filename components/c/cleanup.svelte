<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlrsnrbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlrsnrbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cleanup" {...props}></Icon>
