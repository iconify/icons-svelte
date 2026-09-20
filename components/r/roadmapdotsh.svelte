<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fab0zybii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fab0zybii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:roadmapdotsh" {...props}></Icon>
