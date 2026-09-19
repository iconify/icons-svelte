<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqayoybbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aqayoybbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beanstalk" {...props}></Icon>
