<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzeteibft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzeteibft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:intercom" {...props}></Icon>
