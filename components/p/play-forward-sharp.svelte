<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyp08bp7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyp08bp7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-forward-sharp" {...props}></Icon>
