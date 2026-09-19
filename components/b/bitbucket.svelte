<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tll6oktfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="tll6oktfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bitbucket" {...props}></Icon>
