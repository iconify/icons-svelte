<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh6f6cz1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh6f6cz1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-diagonal-solid" {...props}></Icon>
