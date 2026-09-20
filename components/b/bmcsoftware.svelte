<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bibpq4bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bibpq4bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bmcsoftware" {...props}></Icon>
