<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqf_9pu9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="eqf_9pu9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pushbullet" {...props}></Icon>
