<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfqwt5bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfqwt5bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloudy-filled" {...props}></Icon>
