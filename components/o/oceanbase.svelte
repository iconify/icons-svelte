<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn3a7kb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn3a7kb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:oceanbase" {...props}></Icon>
