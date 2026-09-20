<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyt75nb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyt75nb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:boosty" {...props}></Icon>
