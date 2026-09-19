<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp-5fvbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp-5fvbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:contra" {...props}></Icon>
