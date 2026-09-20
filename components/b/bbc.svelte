<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnk5bq8ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk5bq8ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bbc" {...props}></Icon>
