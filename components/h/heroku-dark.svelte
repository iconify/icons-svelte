<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h31y4wrru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h31y4wrru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:heroku-dark" {...props}></Icon>
