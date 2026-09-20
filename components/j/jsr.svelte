<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufjg9-beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufjg9-beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jsr" {...props}></Icon>
