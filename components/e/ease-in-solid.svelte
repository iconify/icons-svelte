<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwkyo7u3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwkyo7u3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ease-in-solid" {...props}></Icon>
