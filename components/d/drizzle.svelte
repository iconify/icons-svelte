<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyedfo_uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyedfo_uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:drizzle" {...props}></Icon>
